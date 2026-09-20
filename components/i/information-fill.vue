<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s02i13bjj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s02i13bjj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:information-fill" /></template>
