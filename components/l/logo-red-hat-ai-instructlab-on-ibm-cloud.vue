<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/agq-2qutk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="agq-2qutk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:logo-red-hat-ai-instructlab-on-ibm-cloud" /></template>
