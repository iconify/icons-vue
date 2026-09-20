<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vvya7xl9l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vvya7xl9l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:bnb-line" /></template>
