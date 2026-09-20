<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vw34_3bgw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vw34_3bgw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:computer-laptop-solid" /></template>
