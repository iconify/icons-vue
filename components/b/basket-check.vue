<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xc5-3bbpl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xc5-3bbpl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:basket-check" /></template>
