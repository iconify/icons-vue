<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n6_y8j3lm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":344,"height":464};
const content = `<path class="n6_y8j3lm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:directions-run" /></template>
