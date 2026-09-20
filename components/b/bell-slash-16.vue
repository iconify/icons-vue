<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tt5mcm8zj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="tt5mcm8zj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:bell-slash-16" /></template>
