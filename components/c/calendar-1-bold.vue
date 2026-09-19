<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oc2lhnshp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oc2lhnshp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:calendar-1-bold" /></template>
