<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d3g14o-3g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="d3g14o-3g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:live-site" /></template>
