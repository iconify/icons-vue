<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lihl_43df.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lihl_43df"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:fridge-industrial" /></template>
