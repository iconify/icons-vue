<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r-ost6bfw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":300,"height":300};
const content = `<path class="r-ost6bfw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:graphcool" /></template>
