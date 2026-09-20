<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bimt6g92e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="bimt6g92e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:geyser-from-ground" /></template>
