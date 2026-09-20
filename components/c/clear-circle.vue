<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ri_iqnbwl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ri_iqnbwl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:clear-circle" /></template>
