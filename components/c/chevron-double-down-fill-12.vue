<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bm7bzwy4d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="bm7bzwy4d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:chevron-double-down-fill-12" /></template>
