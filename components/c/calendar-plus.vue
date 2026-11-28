<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/leze99baj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="leze99baj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:calendar-plus" /></template>
