<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/js-e04bid.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="js-e04bid"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:layers-intersect-outline" /></template>
