<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/drbstn8ih.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="drbstn8ih"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:hat-2-line" /></template>
