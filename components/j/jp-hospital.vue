<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/purossznf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="purossznf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:jp-hospital" /></template>
