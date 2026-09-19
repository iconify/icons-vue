<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vjlrjeixl.css';
import '../../css/m/m1mt6od4j.css';
import '../../css/p/p_qb8obhm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="vjlrjeixl"/><path class="m1mt6od4j"/><path class="p_qb8obhm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:ibm-engineering-test-mgmt" /></template>
