<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m7zm0u_6f.css';
import '../../css/j/jiqi-hb6a.css';
import '../../css/x/xf-_f2-0r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="m7zm0u_6f"/><path class="jiqi-hb6a"/><path class="xf-_f2-0r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:cocktail-20-bold" /></template>
