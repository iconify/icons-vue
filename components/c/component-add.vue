<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k9g8caczj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":21};
const content = `<path class="k9g8caczj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="system-uicons:component-add" /></template>
