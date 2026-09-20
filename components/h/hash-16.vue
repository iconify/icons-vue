<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cjvos31mt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="cjvos31mt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:hash-16" /></template>
