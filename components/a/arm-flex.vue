<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d8wa-l8ub.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d8wa-l8ub"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:arm-flex" /></template>
