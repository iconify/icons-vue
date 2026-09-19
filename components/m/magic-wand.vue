<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ax753pv4y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ax753pv4y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:magic-wand" /></template>
