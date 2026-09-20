<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k2tiyibie.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="k2tiyibie"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uiw:component" /></template>
