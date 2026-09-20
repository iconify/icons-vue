<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sxo33drqq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="sxo33drqq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:family-restroom-symbol" /></template>
