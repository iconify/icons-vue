<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i3rk9hrsr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i3rk9hrsr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:arrows-down-fill" /></template>
