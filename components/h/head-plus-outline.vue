<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xbc9occ-b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xbc9occ-b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:head-plus-outline" /></template>
