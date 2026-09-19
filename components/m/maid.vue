<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/z/zjpjbki-t.css';
import '../../css/b/b53ts9b6i.css';
import '../../css/f/fvk21rbzp.css';
import '../../css/u/u4c30j0ef.css';
import '../../css/p/p1p-v4bmj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="bi12bsetm"><circle class="zjpjbki-t"/><g class="b53ts9b6i"><path class="fvk21rbzp"/><path class="u4c30j0ef"/><path class="p1p-v4bmj"/></g></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency-color:maid" /></template>
