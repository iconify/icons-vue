<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lrb7icb1k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="lrb7icb1k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:file-doc-filled" /></template>
