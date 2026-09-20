<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cak32ib9d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="cak32ib9d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:folder-minus-outline" /></template>
