<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/y/y8zdmx7kg.css';
import '../../css/y/yh37ftn9n.css';
import '../../css/a/afxk9u7hc.css';
import '../../css/r/rdgy8mlra.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="y8zdmx7kg"/><path class="yh37ftn9n"/><path class="afxk9u7hc"/><path class="rdgy8mlra"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:link-broken-minimalistic-linear" /></template>
