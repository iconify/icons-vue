<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ii08xxbwm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ii08xxbwm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:badge-x" /></template>
