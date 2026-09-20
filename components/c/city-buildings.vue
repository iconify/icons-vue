<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r5s-5corh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="r5s-5corh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:city-buildings" /></template>
