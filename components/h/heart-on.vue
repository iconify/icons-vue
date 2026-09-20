<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c9nik1b9f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="c9nik1b9f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uiw:heart-on" /></template>
