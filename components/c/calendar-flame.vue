<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nnpi_abmg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nnpi_abmg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:calendar-flame" /></template>
