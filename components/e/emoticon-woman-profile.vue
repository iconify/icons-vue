<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hc3cm42dg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hc3cm42dg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:emoticon-woman-profile" /></template>
