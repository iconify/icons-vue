<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l6vg5ubaa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="l6vg5ubaa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo:arrow-right" /></template>
