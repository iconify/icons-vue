<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r4jgbnbwk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="r4jgbnbwk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:inspect" /></template>
