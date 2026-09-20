<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bse-cb6-t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<rect class="bse-cb6-t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:interface-geometric-square-square-geometric-design-shape-shapes" /></template>
