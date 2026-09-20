<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q1z1cpkvz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q1z1cpkvz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:chevron-down-rectangle-filled" /></template>
