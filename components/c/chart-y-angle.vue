<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nuse81brp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="nuse81brp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:chart-y-angle" /></template>
