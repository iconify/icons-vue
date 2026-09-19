<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j9g5xl3gs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="j9g5xl3gs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:layout-panel-right" /></template>
