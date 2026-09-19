<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iw-24x-1s.css';
import '../../css/j/jr59nabqc.css';
import '../../css/m/m2o3sh-9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-outline clr-i-outline-path-1 iw-24x-1s"/><path class="clr-i-outline clr-i-outline-path-2 jr59nabqc"/><path class="m2o3sh-9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:flame-line" /></template>
