<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qx7d-gbhu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="qx7d-gbhu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:grin" /></template>
