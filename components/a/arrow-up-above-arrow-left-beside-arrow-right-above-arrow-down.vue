<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oqemtkn4p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="oqemtkn4p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:arrow-up-above-arrow-left-beside-arrow-right-above-arrow-down" /></template>
