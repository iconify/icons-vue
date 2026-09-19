<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sgix2db9b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="sgix2db9b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:arrows-down-to-people" /></template>
