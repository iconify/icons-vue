<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y-zstjb0n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y-zstjb0n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:arrow-to-left-fill" /></template>
