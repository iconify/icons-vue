<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x-h5mpb_l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="x-h5mpb_l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:creative-commons-pd" /></template>
