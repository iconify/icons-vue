<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dltsm_4ox.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="dltsm_4ox"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uiw:circle-close" /></template>
