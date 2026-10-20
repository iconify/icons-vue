<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g-31_hbov.css';
import '../../css/r/rw2_921jp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="g-31_hbov"/><path class="rw2_921jp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:binoculars-48" /></template>
