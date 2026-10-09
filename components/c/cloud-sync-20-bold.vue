<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/woejr8lkf.css';
import '../../css/h/h8ky2qf0l.css';
import '../../css/w/wbh530b4c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="woejr8lkf"/><path class="h8ky2qf0l"/><path class="wbh530b4c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:cloud-sync-20-bold" /></template>
