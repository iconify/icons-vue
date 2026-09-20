<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r91_16h3q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r91_16h3q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:cash-remove" /></template>
