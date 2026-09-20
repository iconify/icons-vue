<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qaubn2bjf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qaubn2bjf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:door-exit-line" /></template>
