<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cxakesbja.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cxakesbja"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:biscuit-clock" /></template>
