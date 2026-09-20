<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xsgnn88kw.css';
import '../../css/p/ph02kkyzz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="xsgnn88kw"/><path class="ph02kkyzz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:issue-reopened-16" /></template>
