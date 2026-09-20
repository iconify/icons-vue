<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mrs38gvrp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mrs38gvrp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:amo" /></template>
