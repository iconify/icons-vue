<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zi2gxlb-t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="zi2gxlb-t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:arrow-right-to-tall-rectangle-outline" /></template>
