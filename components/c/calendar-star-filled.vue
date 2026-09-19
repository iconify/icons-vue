<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rmasy2qqg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rmasy2qqg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:calendar-star-filled" /></template>
