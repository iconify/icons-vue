<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/niijr9bav.css';
import '../../css/p/pv8augtve.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="niijr9bav"/><path class="pv8augtve"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:food-menu" /></template>
