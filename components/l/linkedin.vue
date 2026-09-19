<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ksa2hs06o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="ksa2hs06o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:linkedin" /></template>
