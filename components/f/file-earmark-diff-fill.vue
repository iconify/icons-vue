<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a_hqktbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="a_hqktbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:file-earmark-diff-fill" /></template>
