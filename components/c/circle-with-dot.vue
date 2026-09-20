<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wdtnx0blw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="wdtnx0blw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:circle-with-dot" /></template>
