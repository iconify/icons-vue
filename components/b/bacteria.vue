<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n_c3t5xbj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n_c3t5xbj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:bacteria" /></template>
