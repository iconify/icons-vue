<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i9ojy9bhp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":768};
const content = `<path class="i9ojy9bhp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:batterytwenty" /></template>
