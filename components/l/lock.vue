<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jo6ajcsyk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jo6ajcsyk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:lock" /></template>
