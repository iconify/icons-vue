<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ruvfvnb8e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ruvfvnb8e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:analyze" /></template>
