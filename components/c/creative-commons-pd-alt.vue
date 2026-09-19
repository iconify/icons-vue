<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nt-g2-3ta.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="nt-g2-3ta"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:creative-commons-pd-alt" /></template>
