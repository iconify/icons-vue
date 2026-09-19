<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jql3tpusm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1664,"height":1664};
const content = `<path class="jql3tpusm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:crop" /></template>
