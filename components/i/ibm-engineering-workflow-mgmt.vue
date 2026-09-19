<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pvccdfbpr.css';
import '../../css/s/s229knb7k.css';
import '../../css/e/e1jcxhbna.css';
import '../../css/i/i-sniivkv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="pvccdfbpr"/><circle class="s229knb7k"/><circle class="e1jcxhbna"/><circle class="i-sniivkv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:ibm-engineering-workflow-mgmt" /></template>
