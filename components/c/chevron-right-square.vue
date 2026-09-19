<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qhsl0kbdt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qhsl0kbdt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:chevron-right-square" /></template>
