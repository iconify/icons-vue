<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e8ps7tb5m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":32};
const content = `<path class="e8ps7tb5m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="et:bike" /></template>
