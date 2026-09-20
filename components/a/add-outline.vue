<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x2tjx8bji.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x2tjx8bji"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:add-outline" /></template>
