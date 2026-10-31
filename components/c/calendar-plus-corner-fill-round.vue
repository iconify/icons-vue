<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lv25jcc7x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lv25jcc7x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:calendar-plus-corner-fill-round" /></template>
