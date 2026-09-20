<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t91dthp7l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="t91dthp7l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="rivet-icons:info-circle-solid" /></template>
