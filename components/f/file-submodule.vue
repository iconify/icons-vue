<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uphm3xb5r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":16};
const content = `<path class="uphm3xb5r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:file-submodule" /></template>
