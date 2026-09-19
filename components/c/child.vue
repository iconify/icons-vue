<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/drp3_i9rj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1152,"height":1632};
const content = `<path class="drp3_i9rj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:child" /></template>
