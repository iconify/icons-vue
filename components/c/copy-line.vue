<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/huoyumh1w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="huoyumh1w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gis:copy-line" /></template>
