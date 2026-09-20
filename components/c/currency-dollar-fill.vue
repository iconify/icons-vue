<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i_-6f0blo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="i_-6f0blo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:currency-dollar-fill" /></template>
