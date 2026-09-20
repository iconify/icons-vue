<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xo324-b7r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="xo324-b7r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:lander" /></template>
