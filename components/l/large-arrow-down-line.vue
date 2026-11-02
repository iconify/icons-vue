<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/guipbacim.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="guipbacim"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:large-arrow-down-line" /></template>
