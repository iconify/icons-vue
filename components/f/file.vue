<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/goohnvfrd.css';
import '../../css/z/z8ck8jbnx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="goohnvfrd"/><path class="z8ck8jbnx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flat-color-icons:file" /></template>
