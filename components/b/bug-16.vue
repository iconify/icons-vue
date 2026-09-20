<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jw5ivpiyk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="jw5ivpiyk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:bug-16" /></template>
