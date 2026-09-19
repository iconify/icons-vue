<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dtiz8krcv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":592,"height":512};
const content = `<path class="dtiz8krcv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-brands:gitkraken" /></template>
