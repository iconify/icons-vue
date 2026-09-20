<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q_galnbdv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="q_galnbdv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:garage-door" /></template>
