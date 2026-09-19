<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r7hu51muq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="r7hu51muq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:affiliatetheme" /></template>
