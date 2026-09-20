<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c2s12l6ub.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="c2s12l6ub"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:file-import-outline" /></template>
