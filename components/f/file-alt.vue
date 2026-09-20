<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p8cfihbbc.css';
import '../../css/q/q2sotebvb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="p8cfihbbc"/><path class="q2sotebvb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nimbus:file-alt" /></template>
