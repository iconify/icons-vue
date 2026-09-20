<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gw-zbzb4r.css';
import '../../css/x/xc1w02vnd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="gw-zbzb4r"/><path class="xc1w02vnd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:design-ruler" /></template>
