<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vezmvbbrx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vezmvbbrx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:hospital-fill" /></template>
