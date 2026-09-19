<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/llzogmbev.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="llzogmbev"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:cylinder" /></template>
