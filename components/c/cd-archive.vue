<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ny7pffhya.css';
import '../../css/h/h4zwanbgt.css';
import '../../css/e/e39ud6bwf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ny7pffhya"/><path class="h4zwanbgt"/><circle class="e39ud6bwf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:cd-archive" /></template>
