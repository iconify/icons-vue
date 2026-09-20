<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/apdsbhtqi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="apdsbhtqi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:bar-outline" /></template>
