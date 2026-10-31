<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c9yenccxz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="c9yenccxz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:eaved-gabled-building-with-window" /></template>
