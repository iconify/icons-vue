<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f9_ipnbhn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f9_ipnbhn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:book-line" /></template>
