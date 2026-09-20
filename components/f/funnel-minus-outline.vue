<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eaof11a0a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eaof11a0a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:funnel-minus-outline" /></template>
