<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a15kkgboi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a15kkgboi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:grass-line" /></template>
