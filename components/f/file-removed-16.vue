<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p8ovashfh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="p8ovashfh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:file-removed-16" /></template>
