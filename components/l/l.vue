<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k83m2lbqg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="k83m2lbqg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:l" /></template>
