<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qs_yneb2b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="qs_yneb2b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:code-16" /></template>
