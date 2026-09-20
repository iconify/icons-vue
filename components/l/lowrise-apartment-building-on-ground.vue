<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x-kg16b2g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="x-kg16b2g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:lowrise-apartment-building-on-ground" /></template>
