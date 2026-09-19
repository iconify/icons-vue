<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qmgh4mdbv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="qmgh4mdbv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:check-double-stroke-16" /></template>
