<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wtv-45bls.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="wtv-45bls"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:gable-roofed-shelter" /></template>
