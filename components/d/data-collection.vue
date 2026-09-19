<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e39ud6bwf.css';
import '../../css/x/xbfcx7b2l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<circle class="e39ud6bwf"/><path class="xbfcx7b2l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:data-collection" /></template>
