<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lx5q3876m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":16};
const content = `<path class="lx5q3876m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:git-merge" /></template>
