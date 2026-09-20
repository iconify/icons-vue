<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iea6d-aqd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iea6d-aqd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:list-check-2-line" /></template>
