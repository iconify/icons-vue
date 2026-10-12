<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qj4-zfdlh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="qj4-zfdlh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:eye-fill-20" /></template>
