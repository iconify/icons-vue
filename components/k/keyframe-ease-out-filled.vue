<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k4b5l8sta.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k4b5l8sta"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:keyframe-ease-out-filled" /></template>
