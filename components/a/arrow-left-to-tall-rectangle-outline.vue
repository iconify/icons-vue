<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kbwzb4byy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="kbwzb4byy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:arrow-left-to-tall-rectangle-outline" /></template>
