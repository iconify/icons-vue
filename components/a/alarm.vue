<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/b/b54a1v37f.css';
import '../../css/y/ymjeb9z3t.css';
import '../../css/d/dngz4nbwj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":17};
const content = `<g class="cuyn6tgcc"><path class="b54a1v37f"/><path clip-rule="evenodd" class="ymjeb9z3t"/><path class="dngz4nbwj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:alarm" /></template>
