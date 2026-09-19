<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vya01ab-y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="vya01ab-y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:deploy-rules" /></template>
