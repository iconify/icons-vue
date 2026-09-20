<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qpjbsdbyr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="qpjbsdbyr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:envelope-open" /></template>
