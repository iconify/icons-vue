<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bmuejzben.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bmuejzben"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:forward-5-fill" /></template>
