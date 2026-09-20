<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cpxhp8q3b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cpxhp8q3b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:database-arrow-down" /></template>
