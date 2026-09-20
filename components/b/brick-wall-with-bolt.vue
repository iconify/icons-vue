<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b2i7cg_sc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="b2i7cg_sc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:brick-wall-with-bolt" /></template>
