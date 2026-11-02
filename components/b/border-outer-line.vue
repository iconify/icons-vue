<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wmh0nlztu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wmh0nlztu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:border-outer-line" /></template>
