<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jq3ztmbcu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="jq3ztmbcu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:aurelia" /></template>
