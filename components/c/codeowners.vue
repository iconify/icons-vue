<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qaiyq5bvp.css';
import '../../css/o/ogar2nbat.css';
import '../../css/r/rxmfttsiy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<g class="qaiyq5bvp"><path class="ogar2nbat"/><circle class="rxmfttsiy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:codeowners" /></template>
