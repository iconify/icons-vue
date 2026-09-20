<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i273_lbzf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i273_lbzf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:command-fill" /></template>
