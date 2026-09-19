<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ecjcxcbix.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ecjcxcbix"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:graphic-stitching-four" /></template>
