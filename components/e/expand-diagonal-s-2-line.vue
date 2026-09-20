<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l3h3sv7mn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l3h3sv7mn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:expand-diagonal-s-2-line" /></template>
