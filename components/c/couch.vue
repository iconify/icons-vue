<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x870m4u-x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="x870m4u-x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:couch" /></template>
