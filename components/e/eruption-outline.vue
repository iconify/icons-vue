<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yv83v9bhs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yv83v9bhs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:eruption-outline" /></template>
