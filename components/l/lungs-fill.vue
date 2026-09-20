<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i2n-jgv6j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i2n-jgv6j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:lungs-fill" /></template>
