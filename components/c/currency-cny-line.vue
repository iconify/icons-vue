<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zohjyxbjg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zohjyxbjg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:currency-cny-line" /></template>
