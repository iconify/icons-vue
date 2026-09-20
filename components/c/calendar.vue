<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/muu8gqd7d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="muu8gqd7d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:calendar" /></template>
