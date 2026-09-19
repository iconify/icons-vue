<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bd0oqeb7g.css';
import '../../css/u/uvsy0xydv.css';
import '../../css/u/uq2nvxbgs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="bd0oqeb7g"/><path class="uvsy0xydv"/><path class="uq2nvxbgs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:arrow-annotation" /></template>
