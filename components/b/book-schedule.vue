<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kfo94lbhx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kfo94lbhx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:book-schedule" /></template>
