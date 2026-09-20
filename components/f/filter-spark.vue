<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d59_tovyd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d59_tovyd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:filter-spark" /></template>
