<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hgej2kbwp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="hgej2kbwp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:git-que-merge-agent-16" /></template>
