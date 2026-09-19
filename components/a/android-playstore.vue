<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rzp-m6bsp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rzp-m6bsp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:android-playstore" /></template>
