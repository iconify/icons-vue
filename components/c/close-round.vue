<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xupq2nozy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xupq2nozy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:close-round" /></template>
