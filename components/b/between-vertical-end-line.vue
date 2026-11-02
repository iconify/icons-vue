<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/irue1o-5n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="irue1o-5n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:between-vertical-end-line" /></template>
