<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oly6fdb5g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="oly6fdb5g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:italic" /></template>
