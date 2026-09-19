<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ounk-qgqs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ounk-qgqs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:clock" /></template>
