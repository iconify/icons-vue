<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ns35eabmg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1792,"height":1536};
const content = `<path class="ns35eabmg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:commenting-o" /></template>
