<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rmratjbob.css';
import '../../css/a/av226wb2v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="rmratjbob"/><path class="av226wb2v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:desert-20" /></template>
