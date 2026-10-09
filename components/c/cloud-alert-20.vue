<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kwup6hyfp.css';
import '../../css/k/k6p64wbai.css';
import '../../css/h/hik87rbbm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="kwup6hyfp"/><path class="k6p64wbai"/><path class="hik87rbbm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:cloud-alert-20" /></template>
