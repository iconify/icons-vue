<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x9nn-b3_g.css';
import '../../css/p/p6k-85b8h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="x9nn-b3_g"/><path class="p6k-85b8h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:file-check-16" /></template>
