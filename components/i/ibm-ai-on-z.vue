<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dbr5kbcpv.css';
import '../../css/l/lckqvt-5g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="dbr5kbcpv"/><path class="lckqvt-5g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:ibm-ai-on-z" /></template>
