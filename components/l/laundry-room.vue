<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zttafl5jh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zttafl5jh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:laundry-room" /></template>
