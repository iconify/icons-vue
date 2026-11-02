<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u5po-6-fe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u5po-6-fe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:lens-convex-fill" /></template>
