<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j-0orrhmh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="j-0orrhmh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo:flow-branch" /></template>
