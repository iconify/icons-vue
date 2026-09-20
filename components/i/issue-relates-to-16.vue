<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dfyu4cbug.css';
import '../../css/o/o95idacva.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="dfyu4cbug"/><path class="o95idacva"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:issue-relates-to-16" /></template>
