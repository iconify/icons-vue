<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w24qb0b6i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w24qb0b6i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:alarm-clock-off" /></template>
