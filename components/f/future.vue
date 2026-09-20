<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/elt0apgww.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="elt0apgww"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="raphael:future" /></template>
