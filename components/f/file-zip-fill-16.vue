<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r_mo4xl-o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="r_mo4xl-o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:file-zip-fill-16" /></template>
