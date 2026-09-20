<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cbsmoquma.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="cbsmoquma"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:bird" /></template>
