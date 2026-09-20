<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ewi3usmnb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ewi3usmnb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:heart-above-outstretched-hand" /></template>
