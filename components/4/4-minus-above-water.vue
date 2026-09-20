<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kk1emt_3m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="kk1emt_3m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:4-minus-above-water" /></template>
