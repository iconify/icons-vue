<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gvedy3bot.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gvedy3bot"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:flag" /></template>
