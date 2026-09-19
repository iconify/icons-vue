<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rk9_gubeh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="rk9_gubeh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:arrow-small-up" /></template>
