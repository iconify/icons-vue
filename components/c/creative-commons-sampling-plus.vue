<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/frzdw0c2f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="frzdw0c2f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:creative-commons-sampling-plus" /></template>
