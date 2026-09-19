<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j2x2j3ulr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="j2x2j3ulr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:arrow-uturn-ccw-left" /></template>
