<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ebldvkbho.css';
import '../../css/z/zcicxlhte.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="ebldvkbho"/><path class="zcicxlhte"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ei:exclamation" /></template>
