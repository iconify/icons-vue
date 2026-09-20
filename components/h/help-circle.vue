<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wy3vwn_zi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wy3vwn_zi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:help-circle" /></template>
