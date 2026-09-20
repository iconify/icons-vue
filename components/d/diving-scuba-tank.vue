<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c6r9v-bax.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c6r9v-bax"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:diving-scuba-tank" /></template>
