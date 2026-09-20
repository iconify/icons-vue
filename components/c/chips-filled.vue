<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ac-lxcc5p.css';
import '../../css/o/ofxdamrpd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ac-lxcc5p"/><path class="ofxdamrpd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:chips-filled" /></template>
