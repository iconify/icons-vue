<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w66kkxbex.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w66kkxbex"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:currency-nigeria-2-fill" /></template>
