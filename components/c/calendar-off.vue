<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yk7l_pq-v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yk7l_pq-v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:calendar-off" /></template>
