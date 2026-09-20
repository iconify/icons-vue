<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ajpqcixii.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ajpqcixii"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:cash-refund" /></template>
