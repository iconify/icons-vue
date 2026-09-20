<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r685v1blj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="r685v1blj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:doc-document" /></template>
