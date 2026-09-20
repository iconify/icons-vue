<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vsbsd2blj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vsbsd2blj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:alt-arrow-up-bold" /></template>
