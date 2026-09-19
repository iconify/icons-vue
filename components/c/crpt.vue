<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sioyz1b8f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="sioyz1b8f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:crpt" /></template>
