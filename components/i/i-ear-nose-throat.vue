<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qqfs981ly.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="qqfs981ly"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="medical-icon:i-ear-nose-throat" /></template>
