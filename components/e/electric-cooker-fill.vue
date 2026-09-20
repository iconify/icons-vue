<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p-41928fx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p-41928fx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:electric-cooker-fill" /></template>
