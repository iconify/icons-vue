<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yjo07wwqz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yjo07wwqz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:keyframe-hold-linear-out-filled" /></template>
