<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kavk_2ber.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kavk_2ber"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:calendar-arrow-up" /></template>
