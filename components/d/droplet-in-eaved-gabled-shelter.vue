<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qb4bqhwjz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="qb4bqhwjz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:droplet-in-eaved-gabled-shelter" /></template>
