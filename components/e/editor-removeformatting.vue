<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rz50v5bwb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="rz50v5bwb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dashicons:editor-removeformatting" /></template>
