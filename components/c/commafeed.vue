<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/scv3-lbfi.css';
import '../../css/z/zlknd4b1p.css';
import '../../css/o/o6k9xwbor.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":6.563,"height":6.563};
const content = `<rect class="scv3-lbfi"/><path class="zlknd4b1p"/><path class="o6k9xwbor"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:commafeed" /></template>
