<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wjgqdudox.css';
import '../../css/c/c-ji3vbvx.css';
import '../../css/g/gk48d415h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="wjgqdudox"/><path class="c-ji3vbvx"/><path class="gk48d415h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:factory-48-bold" /></template>
