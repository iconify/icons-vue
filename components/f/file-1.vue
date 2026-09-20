<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wctfu3bwq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wctfu3bwq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="subway:file-1" /></template>
