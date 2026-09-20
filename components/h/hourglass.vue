<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/en67xgbpz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="en67xgbpz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:hourglass" /></template>
