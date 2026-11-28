<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uvj5spbyz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uvj5spbyz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:ai-face-look-right-solid" /></template>
