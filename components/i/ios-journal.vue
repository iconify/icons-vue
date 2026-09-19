<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jj114hbbv.css';
import '../../css/n/n6f1xofwr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jj114hbbv"/><path class="n6f1xofwr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-journal" /></template>
