<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xo57adrhy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xo57adrhy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:ejs" /></template>
