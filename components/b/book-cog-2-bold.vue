<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gb874-b1e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gb874-b1e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:book-cog-2-bold" /></template>
