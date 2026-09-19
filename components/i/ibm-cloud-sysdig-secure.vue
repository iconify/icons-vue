<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iq-0w-box.css';
import '../../css/w/wxyzcrbfr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="iq-0w-box"/><path class="wxyzcrbfr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:ibm-cloud-sysdig-secure" /></template>
