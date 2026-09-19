<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t-39p3b7m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t-39p3b7m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-brightness" /></template>
