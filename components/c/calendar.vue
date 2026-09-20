<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pc4b3b0tr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="pc4b3b0tr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:calendar" /></template>
