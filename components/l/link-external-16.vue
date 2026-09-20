<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sg-wc6boc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="sg-wc6boc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:link-external-16" /></template>
