<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pelwo0_dp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pelwo0_dp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:grid-dots-solid" /></template>
