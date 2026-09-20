<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gy60gyb7n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gy60gyb7n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:clock-time-one-outline" /></template>
