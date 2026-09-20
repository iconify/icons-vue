<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t3tgi9b1i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="t3tgi9b1i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:freepbx-dark" /></template>
