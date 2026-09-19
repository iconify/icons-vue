<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oe45mab1n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="oe45mab1n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:cube-20-solid" /></template>
