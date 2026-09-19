<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fvyxec2yk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="fvyxec2yk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:arrow-left-from-line" /></template>
