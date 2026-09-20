<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nt_lgabit.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nt_lgabit"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:jolly-roger-outline" /></template>
