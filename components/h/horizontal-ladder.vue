<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x-dmelbmt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="x-dmelbmt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:horizontal-ladder" /></template>
