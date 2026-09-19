<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vqrep7bti.css';
import '../../css/g/g60lgdcxk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="vqrep7bti"/><path class="g60lgdcxk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:data-analytics" /></template>
