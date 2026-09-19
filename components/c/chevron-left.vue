<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y1dfrij3o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="y1dfrij3o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ei:chevron-left" /></template>
