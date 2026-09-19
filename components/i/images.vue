<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c5ykg8liz.css';
import '../../css/d/dcqkl1zes.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="c5ykg8liz"/><path class="dcqkl1zes"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:images" /></template>
