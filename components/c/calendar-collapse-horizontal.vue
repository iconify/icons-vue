<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zw2lmlbdp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zw2lmlbdp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:calendar-collapse-horizontal" /></template>
