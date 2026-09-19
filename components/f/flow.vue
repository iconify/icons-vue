<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n-mwz804j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="n-mwz804j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:flow" /></template>
