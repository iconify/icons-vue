<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kv5vedcrf.css';
import '../../css/h/hao8iibvm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="kv5vedcrf"/><path class="hao8iibvm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:ibm-cloud-direct-link-2-connect" /></template>
