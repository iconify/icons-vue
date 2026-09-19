<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d55dnvb9g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="d55dnvb9g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo:bowl" /></template>
