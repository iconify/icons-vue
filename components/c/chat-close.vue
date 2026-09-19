<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e8r-j1bhp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e8r-j1bhp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:chat-close" /></template>
