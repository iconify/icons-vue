<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lil__im4t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="lil__im4t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo:circular-graph" /></template>
