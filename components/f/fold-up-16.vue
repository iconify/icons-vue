<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hhosj8bpp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="hhosj8bpp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:fold-up-16" /></template>
