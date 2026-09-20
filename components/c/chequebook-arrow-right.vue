<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r60oz_agq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r60oz_agq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:chequebook-arrow-right" /></template>
