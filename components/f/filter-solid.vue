<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tsm8jabvs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="tsm8jabvs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="rivet-icons:filter-solid" /></template>
