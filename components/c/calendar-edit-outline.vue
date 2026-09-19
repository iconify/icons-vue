<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/srulk4bpq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="srulk4bpq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:calendar-edit-outline" /></template>
