<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g4o1ah-nw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g4o1ah-nw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:calendars" /></template>
