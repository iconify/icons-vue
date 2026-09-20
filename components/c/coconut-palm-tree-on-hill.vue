<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wf7bxabmy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="wf7bxabmy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:coconut-palm-tree-on-hill" /></template>
