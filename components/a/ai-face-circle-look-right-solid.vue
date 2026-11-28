<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u0d94nbog.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u0d94nbog"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:ai-face-circle-look-right-solid" /></template>
