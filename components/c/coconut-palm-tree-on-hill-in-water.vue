<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qq89bn_un.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="qq89bn_un"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:coconut-palm-tree-on-hill-in-water" /></template>
