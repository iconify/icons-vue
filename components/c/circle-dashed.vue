<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gjy379omm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gjy379omm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:circle-dashed" /></template>
