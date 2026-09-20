<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qva2j-bqj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qva2j-bqj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="academicons:doi" /></template>
