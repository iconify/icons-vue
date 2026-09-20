<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l-3jc2mnr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l-3jc2mnr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:favorite-box-multiple-outline" /></template>
