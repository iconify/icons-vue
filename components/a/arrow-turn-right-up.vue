<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hx946b01g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="hx946b01g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:arrow-turn-right-up" /></template>
