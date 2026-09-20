<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jiix6ccxn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jiix6ccxn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:biscuit-minus" /></template>
