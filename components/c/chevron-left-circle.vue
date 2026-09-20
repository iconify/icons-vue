<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pc13uuh3n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pc13uuh3n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:chevron-left-circle" /></template>
