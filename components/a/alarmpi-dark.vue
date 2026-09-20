<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bo2057bxh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bo2057bxh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:alarmpi-dark" /></template>
