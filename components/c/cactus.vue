<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/c/c_bx4-bom.css';
import '../../css/p/pe9nqsbht.css';
import '../../css/n/ne_8u4n5c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="c_bx4-bom"/><path class="pe9nqsbht"/><path class="ne_8u4n5c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-flat:cactus" /></template>
