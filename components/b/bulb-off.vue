<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q9ox9hben.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q9ox9hben"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="humbleicons:bulb-off" /></template>
