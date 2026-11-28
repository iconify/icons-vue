<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lqh8_rbrc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lqh8_rbrc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:ai-face-look-down-solid" /></template>
