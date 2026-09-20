<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yp5oh5bdg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yp5oh5bdg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:human-female-female-child" /></template>
