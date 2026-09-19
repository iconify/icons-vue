<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ranskxjod.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":432,"height":432};
const content = `<path class="ranskxjod"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:alarm" /></template>
