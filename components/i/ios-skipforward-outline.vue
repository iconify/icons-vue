<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hc-22ebky.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hc-22ebky"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-skipforward-outline" /></template>
