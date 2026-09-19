<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e_6xd8_wg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":368,"height":384};
const content = `<path class="e_6xd8_wg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:airline-seat-legroom-reduced" /></template>
