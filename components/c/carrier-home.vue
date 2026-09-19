<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/far6pwong.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="far6pwong"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:carrier-home" /></template>
