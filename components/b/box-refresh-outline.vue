<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ou99r_79m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ou99r_79m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:box-refresh-outline" /></template>
