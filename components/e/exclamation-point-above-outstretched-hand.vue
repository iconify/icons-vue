<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cccwf_yei.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="cccwf_yei"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:exclamation-point-above-outstretched-hand" /></template>
