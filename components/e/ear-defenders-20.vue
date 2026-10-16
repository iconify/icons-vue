<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/syjj109cb.css';
import '../../css/y/yk0otz46s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="syjj109cb"/><path class="yk0otz46s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:ear-defenders-20" /></template>
