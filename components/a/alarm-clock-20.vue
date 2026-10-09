<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fbeq0b47x.css';
import '../../css/b/b40519b-w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="fbeq0b47x"/><path class="b40519b-w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:alarm-clock-20" /></template>
