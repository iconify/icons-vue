<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f7w08kctd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f7w08kctd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:chevron-first-fill" /></template>
