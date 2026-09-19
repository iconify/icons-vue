<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/abo0go4gu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="abo0go4gu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:bracket-dot" /></template>
