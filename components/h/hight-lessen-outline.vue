<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dsar8eb2v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="dsar8eb2v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:hight-lessen-outline" /></template>
