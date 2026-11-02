<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cap6s5brd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cap6s5brd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:alarm-smoke-fill" /></template>
