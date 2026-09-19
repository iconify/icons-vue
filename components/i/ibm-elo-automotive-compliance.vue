<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xl_msvlzl.css';
import '../../css/q/q6zptzlwz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="xl_msvlzl"/><path class="q6zptzlwz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:ibm-elo-automotive-compliance" /></template>
