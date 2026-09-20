<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/umd0n7wwl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="umd0n7wwl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:arrow-left-bottom-bold" /></template>
