<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r9-3teqfy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="r9-3teqfy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:fold-16" /></template>
