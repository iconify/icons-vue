<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/drupv_sdw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="drupv_sdw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:coins-minus" /></template>
