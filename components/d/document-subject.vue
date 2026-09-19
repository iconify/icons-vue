<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/ds1hiib0s.css';
import '../../css/q/qth2s3b6m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ds1hiib0s"/><path class="qth2s3b6m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:document-subject" /></template>
