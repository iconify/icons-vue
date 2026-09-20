<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fmyk-nbco.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="fmyk-nbco"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:close-small-outline" /></template>
