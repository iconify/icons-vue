<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iud-r9o8j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iud-r9o8j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:arrow-up5" /></template>
