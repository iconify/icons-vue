<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r42xyg14h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r42xyg14h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-cyber:binocular-1" /></template>
