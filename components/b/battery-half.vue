<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r9ciw2bty.css';
import '../../css/l/lnzzmyg9g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="r9ciw2bty"/><path class="lnzzmyg9g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:battery-half" /></template>
