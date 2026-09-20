<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ot32r4bbb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ot32r4bbb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:dots-hexagon-solid" /></template>
