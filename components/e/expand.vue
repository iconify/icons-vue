<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jtvh7v3ee.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="jtvh7v3ee"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="raphael:expand" /></template>
