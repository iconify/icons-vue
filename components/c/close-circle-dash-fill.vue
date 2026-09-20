<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w739r15xw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w739r15xw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:close-circle-dash-fill" /></template>
