<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i82zxjp8v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i82zxjp8v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:align-horizontal-center" /></template>
