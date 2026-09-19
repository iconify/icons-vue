<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sjd_c8fym.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="sjd_c8fym"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:git-fetch" /></template>
