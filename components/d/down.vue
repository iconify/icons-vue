<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z3pbgcg6r.css';
import '../../css/e/e052tbbpy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="z3pbgcg6r"/><path class="e052tbbpy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:down" /></template>
