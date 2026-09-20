<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y64eztbbp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="y64eztbbp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="rivet-icons:check-circle-solid" /></template>
