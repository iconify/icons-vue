<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mzngxbbwa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mzngxbbwa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-snowy" /></template>
