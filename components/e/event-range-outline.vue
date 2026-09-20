<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/whroh-seh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="whroh-seh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:event-range-outline" /></template>
