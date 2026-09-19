<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r_eg6bc1k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="r_eg6bc1k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:intensity-concentration-bioassays" /></template>
