<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y0td-222v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="y0td-222v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo:briefcase" /></template>
