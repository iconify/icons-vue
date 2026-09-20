<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bwhco13bl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":16};
const content = `<path class="bwhco13bl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:file" /></template>
