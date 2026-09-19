<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tjppjp8yg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tjppjp8yg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="guidance:hiking" /></template>
