<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u4xae4spt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u4xae4spt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:arrow-thick-up-4-bold" /></template>
