<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/odagw8btu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="odagw8btu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:foot-print" /></template>
