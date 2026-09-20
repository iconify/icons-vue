<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mst7sz6bi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="mst7sz6bi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:burger-and-drink-cup-with-straw" /></template>
