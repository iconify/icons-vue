<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fzv1a3tvp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fzv1a3tvp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:broccoli-fill" /></template>
