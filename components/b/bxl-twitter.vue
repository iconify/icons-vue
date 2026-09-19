<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lvjs-pbfx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lvjs-pbfx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxl-twitter" /></template>
