<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mgygprbzp.css';
import '../../css/n/nkbsn0brg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="mgygprbzp"/><path class="nkbsn0brg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:edit-undo-fill-12" /></template>
