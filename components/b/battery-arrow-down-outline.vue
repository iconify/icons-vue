<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zzdg_bqbm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zzdg_bqbm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:battery-arrow-down-outline" /></template>
