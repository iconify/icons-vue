<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/arq7f-vxj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="arq7f-vxj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:html5-shield" /></template>
