<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/chq5labnj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="chq5labnj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bitcoin-icons:alert-outline" /></template>
