<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ulnrl9bri.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ulnrl9bri"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:history-anticlockwise-fill" /></template>
