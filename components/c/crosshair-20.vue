<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mb1oskbsf.css';
import '../../css/e/eu4b83byw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="mb1oskbsf"/><path class="eu4b83byw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:crosshair-20" /></template>
