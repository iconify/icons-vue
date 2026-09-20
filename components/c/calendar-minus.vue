<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mygswab1f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mygswab1f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:calendar-minus" /></template>
