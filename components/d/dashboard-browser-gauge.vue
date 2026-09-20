<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gfm4-3b6w.css';
import '../../css/e/es9h9dxow.css';
import '../../css/b/b8w7fnbwz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gfm4-3b6w"/><path class="es9h9dxow"/><path class="b8w7fnbwz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand:dashboard-browser-gauge" /></template>
