<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/shzc-6b4p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="shzc-6b4p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:home" /></template>
