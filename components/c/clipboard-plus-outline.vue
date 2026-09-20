<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tbxuu6bvq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tbxuu6bvq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:clipboard-plus-outline" /></template>
