<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cr8zq3bce.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cr8zq3bce"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:layout-bottom-line" /></template>
