<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h921llb8w.css';
import '../../css/a/ausrfdcxh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="h921llb8w"/><path class="ausrfdcxh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:charging-schedule-20-bold" /></template>
