<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u63w3k6_x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u63w3k6_x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:escalator-down-fill" /></template>
