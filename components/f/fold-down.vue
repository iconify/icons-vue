<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wvn6i9e6r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":16};
const content = `<path class="wvn6i9e6r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:fold-down" /></template>
