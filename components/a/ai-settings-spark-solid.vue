<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ius_95bmu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="ius_95bmu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:ai-settings-spark-solid" /></template>
