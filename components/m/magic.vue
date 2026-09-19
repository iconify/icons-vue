<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rujiq5bwm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1664,"height":1664};
const content = `<path class="rujiq5bwm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:magic" /></template>
