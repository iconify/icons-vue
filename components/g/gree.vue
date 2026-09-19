<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w6i8h_b-a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":618,"height":704};
const content = `<path class="w6i8h_b-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:gree" /></template>
