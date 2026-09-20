<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/doctjlc3v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="doctjlc3v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:lock" /></template>
