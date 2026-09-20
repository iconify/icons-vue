<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tq6_1ju_x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tq6_1ju_x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:download" /></template>
