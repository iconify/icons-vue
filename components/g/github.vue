<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dtvrf6dgm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dtvrf6dgm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:github" /></template>
