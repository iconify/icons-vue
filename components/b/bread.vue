<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mkn43-b1g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="mkn43-b1g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="marketeq:bread" /></template>
