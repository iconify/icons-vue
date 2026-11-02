<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w_2f6ubtf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w_2f6ubtf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:fan-direction-front-fill" /></template>
