<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lr168oaij.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lr168oaij"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:arrow-left-fill" /></template>
