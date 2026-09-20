<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g9v62pbcd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g9v62pbcd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteor-icons:arrow-trend-down" /></template>
