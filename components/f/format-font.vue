<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k672u9bsy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k672u9bsy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:format-font" /></template>
