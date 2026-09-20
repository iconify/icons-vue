<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f52y9dbtb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="f52y9dbtb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-line-icons:logout" /></template>
