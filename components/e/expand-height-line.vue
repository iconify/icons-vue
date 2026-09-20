<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hm5xk5b_g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hm5xk5b_g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:expand-height-line" /></template>
