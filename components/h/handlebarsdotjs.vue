<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s2tsr8glm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s2tsr8glm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:handlebarsdotjs" /></template>
