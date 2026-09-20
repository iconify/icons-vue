<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t4ylb3_td.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t4ylb3_td"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:format-pilcrow" /></template>
