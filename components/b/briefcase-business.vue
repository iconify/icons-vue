<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tv89s0poi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tv89s0poi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:briefcase-business" /></template>
