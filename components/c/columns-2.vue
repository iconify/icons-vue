<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qx98cuble.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="qx98cuble"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:columns-2" /></template>
