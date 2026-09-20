<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ijvvyibbs.css';
import '../../css/n/n_v2xfr4l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ijvvyibbs"/><path class="n_v2xfr4l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:calendar-envelope" /></template>
