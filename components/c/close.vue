<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kztwflb_b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":40,"height":40};
const content = `<path class="kztwflb_b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iwwa:close" /></template>
