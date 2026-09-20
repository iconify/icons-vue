<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kihstx6sx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="kihstx6sx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:exclamation-point-beside-question-mark" /></template>
