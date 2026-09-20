<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p7n0xbc9y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="p7n0xbc9y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uiw:cut" /></template>
