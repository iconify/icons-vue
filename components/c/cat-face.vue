<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e2-2dm4yo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="e2-2dm4yo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:cat-face" /></template>
