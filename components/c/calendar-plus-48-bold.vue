<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vwjkdv1oe.css';
import '../../css/b/b3suifbrv.css';
import '../../css/k/k_owl0bao.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="vwjkdv1oe"/><path class="b3suifbrv"/><path class="k_owl0bao"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:calendar-plus-48-bold" /></template>
