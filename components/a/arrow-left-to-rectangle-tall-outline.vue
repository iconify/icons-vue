<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ec3vx5m2n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ec3vx5m2n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:arrow-left-to-rectangle-tall-outline" /></template>
