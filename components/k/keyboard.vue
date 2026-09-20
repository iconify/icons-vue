<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k-9w4jb6k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="k-9w4jb6k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:keyboard" /></template>
