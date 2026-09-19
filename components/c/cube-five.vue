<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j3btvb10h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="j3btvb10h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:cube-five" /></template>
