<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u65hmsmhq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1792,"height":1536};
const content = `<path class="u65hmsmhq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:fast-backward" /></template>
