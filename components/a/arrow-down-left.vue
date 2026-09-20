<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/we2rg-n4z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="we2rg-n4z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:arrow-down-left" /></template>
