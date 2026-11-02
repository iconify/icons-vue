<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/swaptwbdd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="swaptwbdd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:layout-8-line" /></template>
