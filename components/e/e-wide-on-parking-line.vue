<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jyse3869w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="jyse3869w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:e-wide-on-parking-line" /></template>
