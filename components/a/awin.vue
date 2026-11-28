<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jpholnzeo.css';
import '../../css/t/t3zbj22fa.css';
import '../../css/j/j7seq4bbf.css';
import '../../css/z/z3ck36bfj.css';
import '../../css/e/e3-urhbop.css';
import '../../css/c/cs994mb8w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jpholnzeo"/><path class="t3zbj22fa"/><path class="j7seq4bbf"/><path class="z3ck36bfj"/><path class="e3-urhbop"/><path class="cs994mb8w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:awin" /></template>
