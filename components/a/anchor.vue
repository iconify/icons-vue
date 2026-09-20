<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xfkgk1l5g.css';
import '../../css/u/ugxf3ybrs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="xfkgk1l5g"/><path class="ugxf3ybrs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:anchor" /></template>
