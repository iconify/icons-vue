<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oo1dt-bjs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="oo1dt-bjs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dashicons:align-pull-right" /></template>
