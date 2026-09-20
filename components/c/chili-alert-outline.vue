<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wejbnw1yz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wejbnw1yz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:chili-alert-outline" /></template>
