<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xrnc0612b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xrnc0612b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:colorize" /></template>
