<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hcc333z4c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hcc333z4c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:cloud" /></template>
