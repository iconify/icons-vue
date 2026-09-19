<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kptyhh2yz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="kptyhh2yz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:github-project" /></template>
