<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w16t2pppu.css';
import '../../css/q/q9-pcgbxd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="w16t2pppu"/><path class="q9-pcgbxd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nimbus:home" /></template>
