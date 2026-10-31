<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s8oiug1hh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="s8oiug1hh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:gabled-building-with-flag-and-door" /></template>
