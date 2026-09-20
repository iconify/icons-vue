<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f7y3x5kge.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="f7y3x5kge"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:file-diff-16" /></template>
