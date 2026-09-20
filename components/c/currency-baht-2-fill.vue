<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mdfi2l-qu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mdfi2l-qu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:currency-baht-2-fill" /></template>
