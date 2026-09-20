<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gg13tolxm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gg13tolxm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:human-hand-truck" /></template>
