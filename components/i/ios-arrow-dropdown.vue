<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xv3w-bboh.css';
import '../../css/e/e0us24bst.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xv3w-bboh"/><path class="e0us24bst"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-arrow-dropdown" /></template>
