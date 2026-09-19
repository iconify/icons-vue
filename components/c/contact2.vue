<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/som5wvb2y.css';
import '../../css/q/qj2dxhekm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="som5wvb2y"/><path class="qj2dxhekm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:contact2" /></template>
