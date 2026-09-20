<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g9h3vbbla.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="g9h3vbbla"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:briefcase-with-circular-pill-and-capsule-pill" /></template>
