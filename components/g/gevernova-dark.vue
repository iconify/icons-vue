<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rig-ls45m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1545,"height":1544};
const content = `<path class="rig-ls45m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:gevernova-dark" /></template>
