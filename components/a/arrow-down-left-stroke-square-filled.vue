<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s4cirqb4x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s4cirqb4x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:arrow-down-left-stroke-square-filled" /></template>
