<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/czsubus_w.css';
import '../../css/r/rfqi4njim.css';
import '../../css/b/b6fhfryel.css';
import '../../css/c/c3v_g_mjq.css';
import '../../css/c/c-jdkp9ce.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="czsubus_w"/><circle class="rfqi4njim"/><path class="b6fhfryel"/><circle class="c3v_g_mjq"/><path class="c-jdkp9ce"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:ibm-watsonx-code-assistant-for-z-refactor" /></template>
