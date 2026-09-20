<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vhvoj9eul.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vhvoj9eul"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:chevron-double-left" /></template>
