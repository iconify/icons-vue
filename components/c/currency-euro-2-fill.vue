<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w5e2sw09k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w5e2sw09k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:currency-euro-2-fill" /></template>
