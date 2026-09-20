<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f4p__bc9g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="f4p__bc9g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:default" /></template>
