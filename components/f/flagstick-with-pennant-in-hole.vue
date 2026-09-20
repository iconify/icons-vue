<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/md80vybsv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="md80vybsv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:flagstick-with-pennant-in-hole" /></template>
