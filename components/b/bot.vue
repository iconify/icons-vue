<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/siav9f5cp.css';
import '../../css/j/jjcws580t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="siav9f5cp"/><path class="jjcws580t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:bot" /></template>
