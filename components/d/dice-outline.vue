<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/r/rlijx1q8p.css';
import '../../css/o/oulh0ib2a.css';
import '../../css/v/vs7ixeb9e.css';
import '../../css/k/k2wokiz2q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="rlijx1q8p"/><path class="oulh0ib2a"/><path class="vs7ixeb9e"/><path class="k2wokiz2q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:dice-outline" /></template>
