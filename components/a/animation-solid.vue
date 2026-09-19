<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y0izj7bsj.css';
import '../../css/p/p64c9l0on.css';
import '../../css/a/aexcjlr_h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="y0izj7bsj"/><path class="p64c9l0on"/><path class="aexcjlr_h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:animation-solid" /></template>
