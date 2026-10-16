<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yefgfcbum.css';
import '../../css/w/wp8j1tmrq.css';
import '../../css/r/rb9owibwy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="yefgfcbum"/><path class="wp8j1tmrq"/><path class="rb9owibwy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:file-clock-48-bold" /></template>
