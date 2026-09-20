<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g6y0rwcxe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g6y0rwcxe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:chef-hat-line" /></template>
