<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pu75xnflc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="pu75xnflc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:bowling" /></template>
