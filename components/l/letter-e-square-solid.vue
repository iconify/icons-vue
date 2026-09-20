<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x4k47t24h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x4k47t24h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:letter-e-square-solid" /></template>
