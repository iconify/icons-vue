<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m6i42hbhh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m6i42hbhh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:layout-4-line" /></template>
