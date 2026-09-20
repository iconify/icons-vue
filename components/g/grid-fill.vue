<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jtq7a3bun.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jtq7a3bun"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:grid-fill" /></template>
