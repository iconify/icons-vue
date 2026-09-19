<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/grltfp37s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1200,"height":1200};
const content = `<path class="grltfp37s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="el:car" /></template>
