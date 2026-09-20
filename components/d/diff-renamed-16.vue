<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tkc-cckkh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="tkc-cckkh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:diff-renamed-16" /></template>
