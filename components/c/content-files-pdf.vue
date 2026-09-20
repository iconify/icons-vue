<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oot5ivbbj.css';
import '../../css/n/n3wlgc-qo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="oot5ivbbj"/><path class="n3wlgc-qo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:content-files-pdf" /></template>
