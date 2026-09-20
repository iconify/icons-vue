<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ucy80rbgu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ucy80rbgu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:coughing-face-with-phlegm" /></template>
