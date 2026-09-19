<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tp35ndvma.css';
import '../../css/x/xyg2e4p_h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="tp35ndvma"/><path class="xyg2e4p_h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-color-fill" /></template>
