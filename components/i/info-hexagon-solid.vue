<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pt0p3obti.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pt0p3obti"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:info-hexagon-solid" /></template>
