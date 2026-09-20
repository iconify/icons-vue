<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/panl95b6g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="panl95b6g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:ai-email-generator-spark-solid" /></template>
