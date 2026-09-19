<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o55fdr30x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="o55fdr30x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:chevron-circle-right" /></template>
