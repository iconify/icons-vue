<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/irvmvcb2e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="irvmvcb2e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:lightbulb-on-80" /></template>
