<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cvfy4cbeq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="cvfy4cbeq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:geyser-from-water" /></template>
