<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ky4bs7b5q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ky4bs7b5q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:home-09" /></template>
