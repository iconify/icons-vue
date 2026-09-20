<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pftvle2xc.css';
import '../../css/c/cxuk12djg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="pftvle2xc"/><path class="cxuk12djg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:feed-issue-open-16" /></template>
