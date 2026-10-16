<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q2qly6b8v.css';
import '../../css/y/yxx6x7qnn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="q2qly6b8v"/><path class="yxx6x7qnn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:heat-pump-hybrid-20-bold" /></template>
