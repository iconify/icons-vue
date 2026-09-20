<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/se_k1pijo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="se_k1pijo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:cairn-beside-trail-blazes-down" /></template>
