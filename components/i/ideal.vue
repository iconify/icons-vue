<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y0397_6ub.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="y0397_6ub"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:ideal" /></template>
