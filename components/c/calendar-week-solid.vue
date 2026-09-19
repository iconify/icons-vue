<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vd6_-9b4y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vd6_-9b4y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:calendar-week-solid" /></template>
