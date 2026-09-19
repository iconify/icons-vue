<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tc6-f2oia.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="tc6-f2oia"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:github-inverted" /></template>
