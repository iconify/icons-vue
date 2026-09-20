<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kt9sd4r-w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="kt9sd4r-w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:fallout-shelter-symbol" /></template>
