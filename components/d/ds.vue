<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e937cn8lw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e937cn8lw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:ds" /></template>
