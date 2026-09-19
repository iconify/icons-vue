<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cl9-1ibeu.css';
import '../../css/m/m3no34b0f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cl9-1ibeu"/><path class="m3no34b0f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:link-alt" /></template>
