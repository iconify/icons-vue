<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fuyyhybke.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fuyyhybke"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:battery-1-line" /></template>
