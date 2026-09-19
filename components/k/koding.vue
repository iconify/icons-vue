<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qnewt-bzr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="qnewt-bzr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:koding" /></template>
