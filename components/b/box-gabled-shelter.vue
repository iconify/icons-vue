<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uj35rnq-g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="uj35rnq-g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:box-gabled-shelter" /></template>
