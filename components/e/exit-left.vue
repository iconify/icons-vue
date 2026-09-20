<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wudkh2r8y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":21};
const content = `<path class="wudkh2r8y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="system-uicons:exit-left" /></template>
