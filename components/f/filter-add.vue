<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uc8zf3buz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uc8zf3buz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:filter-add" /></template>
