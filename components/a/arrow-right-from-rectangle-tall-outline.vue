<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tgxrp-bwh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="tgxrp-bwh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:arrow-right-from-rectangle-tall-outline" /></template>
