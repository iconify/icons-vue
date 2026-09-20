<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e-n6sx-7m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="e-n6sx-7m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:file-directory-fill-16" /></template>
