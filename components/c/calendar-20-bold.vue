<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g7qx85bwi.css';
import '../../css/j/jcidjcczi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="g7qx85bwi"/><path class="jcidjcczi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:calendar-20-bold" /></template>
