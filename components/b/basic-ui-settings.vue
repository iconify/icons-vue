<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ew__pnb5s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="ew__pnb5s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-block:basic-ui-settings" /></template>
