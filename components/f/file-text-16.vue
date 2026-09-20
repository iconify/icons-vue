<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pmdn2ybsd.css';
import '../../css/r/rnvgnfbbf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="pmdn2ybsd"/><path clip-rule="evenodd" class="rnvgnfbbf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:file-text-16" /></template>
