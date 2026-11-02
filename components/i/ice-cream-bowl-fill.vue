<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c7bq2hpiq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c7bq2hpiq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:ice-cream-bowl-fill" /></template>
