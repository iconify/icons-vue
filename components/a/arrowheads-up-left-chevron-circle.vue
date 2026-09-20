<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bntqr-xzn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="bntqr-xzn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-block:arrowheads-up-left-chevron-circle" /></template>
