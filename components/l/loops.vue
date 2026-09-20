<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oejd0_69w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oejd0_69w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:loops" /></template>
