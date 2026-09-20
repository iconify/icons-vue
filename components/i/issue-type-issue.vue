<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ly9cwgt1f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="ly9cwgt1f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pajamas:issue-type-issue" /></template>
