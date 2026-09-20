<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eey73sbct.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eey73sbct"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:bookmark-minus" /></template>
