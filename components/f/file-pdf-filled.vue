<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z520-zi2f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="z520-zi2f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:file-pdf-filled" /></template>
