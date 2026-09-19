<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pp1cw5b_a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pp1cw5b_a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:arrows-to-dot" /></template>
