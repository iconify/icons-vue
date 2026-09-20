<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zk2cnabil.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="zk2cnabil"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:diamond-alt" /></template>
