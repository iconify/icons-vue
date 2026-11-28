<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ukk04mbry.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ukk04mbry"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:calendar-question" /></template>
