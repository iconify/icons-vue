<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e-qfjb-7g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="e-qfjb-7g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:gg" /></template>
