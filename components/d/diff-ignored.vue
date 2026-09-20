<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c_9fyk9vg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":16};
const content = `<path class="c_9fyk9vg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:diff-ignored" /></template>
