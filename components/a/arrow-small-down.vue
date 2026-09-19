<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aa421_b6g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="aa421_b6g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:arrow-small-down" /></template>
