<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ag-domk8v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ag-domk8v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:logseq-dark" /></template>
