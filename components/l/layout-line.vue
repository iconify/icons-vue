<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l0lqcccqi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l0lqcccqi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:layout-line" /></template>
