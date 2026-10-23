<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gykblbbss.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="gykblbbss"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:check-agent-16" /></template>
