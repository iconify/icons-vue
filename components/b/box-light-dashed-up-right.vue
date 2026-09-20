<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oqw21yb_s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="oqw21yb_s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:box-light-dashed-up-right" /></template>
