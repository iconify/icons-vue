<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ow40lcb2l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ow40lcb2l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:dtube" /></template>
