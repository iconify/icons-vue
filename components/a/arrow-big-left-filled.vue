<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pdneytbew.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pdneytbew"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:arrow-big-left-filled" /></template>
