<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k7fjzjbav.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="k7fjzjbav"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:arrow-right" /></template>
