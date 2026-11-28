<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yfjr1obov.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="yfjr1obov"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:geyser-outline-from-water" /></template>
