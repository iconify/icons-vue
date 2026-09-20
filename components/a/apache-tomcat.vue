<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tuzx40mug.css';
import '../../css/w/wkccvue1w.css';
import '../../css/y/yur3l-b2x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="tuzx40mug"/><path class="wkccvue1w"/><path class="yur3l-b2x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:apache-tomcat" /></template>
