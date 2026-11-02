<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g3i4-s0jp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g3i4-s0jp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:heart-off-line" /></template>
