<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eoj0_sxob.css';
import '../../css/v/voqlvbrhf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="eoj0_sxob"/><path class="voqlvbrhf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:issue-closed-16" /></template>
