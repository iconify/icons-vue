<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pwmxdo9_h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pwmxdo9_h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:discount-shape-filled" /></template>
