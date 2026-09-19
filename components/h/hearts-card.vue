<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z4g5dwuee.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":512};
const content = `<path class="z4g5dwuee"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:hearts-card" /></template>
