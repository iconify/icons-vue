<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tn2aw68ax.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="tn2aw68ax"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:key-modern" /></template>
