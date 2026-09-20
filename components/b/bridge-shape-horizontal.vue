<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b7fgytnir.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="b7fgytnir"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:bridge-shape-horizontal" /></template>
