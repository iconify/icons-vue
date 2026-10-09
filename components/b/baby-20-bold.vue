<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lbyywfnen.css';
import '../../css/h/hz4iidbyt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="lbyywfnen"/><path class="hz4iidbyt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:baby-20-bold" /></template>
