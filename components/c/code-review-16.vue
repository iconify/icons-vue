<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nvlv85b6y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="nvlv85b6y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:code-review-16" /></template>
