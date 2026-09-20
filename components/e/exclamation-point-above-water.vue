<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g5p60rbrg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="g5p60rbrg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:exclamation-point-above-water" /></template>
