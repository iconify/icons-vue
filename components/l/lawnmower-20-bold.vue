<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zudjy0tbx.css';
import '../../css/t/te4hhac8s.css';
import '../../css/b/bat89cbei.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="zudjy0tbx"/><path class="te4hhac8s"/><path class="bat89cbei"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:lawnmower-20-bold" /></template>
