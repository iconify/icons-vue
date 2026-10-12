<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sbgf1vj4o.css';
import '../../css/l/ldkcw25ft.css';
import '../../css/j/jv0fgj_2y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="sbgf1vj4o"/><path class="ldkcw25ft"/><path class="jv0fgj_2y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:blood-drop-20-bold" /></template>
