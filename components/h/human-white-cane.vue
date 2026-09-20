<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fhmw1jw7q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fhmw1jw7q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:human-white-cane" /></template>
