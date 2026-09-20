<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j3olpq2tb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j3olpq2tb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:expand-diagonal-s-fill" /></template>
