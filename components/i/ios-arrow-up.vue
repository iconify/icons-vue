<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ewu4g9brn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ewu4g9brn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-arrow-up" /></template>
