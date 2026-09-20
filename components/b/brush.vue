<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mfc93_bxb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mfc93_bxb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:brush" /></template>
