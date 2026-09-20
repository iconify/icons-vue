<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iz2uc7bmz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="iz2uc7bmz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:ellipse-arc" /></template>
