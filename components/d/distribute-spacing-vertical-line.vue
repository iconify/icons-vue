<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nvb3wvk0b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nvb3wvk0b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:distribute-spacing-vertical-line" /></template>
