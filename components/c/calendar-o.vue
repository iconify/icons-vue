<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mut1umbgi.css';
import '../../css/p/pt8jm_b_y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="mut1umbgi"/><path class="pt8jm_b_y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:calendar-o" /></template>
