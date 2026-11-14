<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kmq8itb1q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kmq8itb1q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:briefcase-08" /></template>
