<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e3k_j8bpc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="e3k_j8bpc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:bear-spray-can-with-spray-and-euro" /></template>
