<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qimuysblv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":512};
const content = `<path class="qimuysblv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:file-video" /></template>
