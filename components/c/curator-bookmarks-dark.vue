<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qjdk-tbmr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qjdk-tbmr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:curator-bookmarks-dark" /></template>
