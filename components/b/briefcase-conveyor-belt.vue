<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g615euncf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g615euncf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:briefcase-conveyor-belt" /></template>
