<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cu870r4lf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cu870r4lf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:information-2-fill" /></template>
