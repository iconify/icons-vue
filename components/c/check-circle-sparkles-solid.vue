<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uojy0ix4w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uojy0ix4w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:check-circle-sparkles-solid" /></template>
