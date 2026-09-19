<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qmiqepbty.css';
import '../../css/j/j7xllpb6d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="qmiqepbty"/><path class="j7xllpb6d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:ibm-cloud-direct-link-2-dedicated" /></template>
