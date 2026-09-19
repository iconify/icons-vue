<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lo6j7xbls.css';
import '../../css/v/vrpmrdbjw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="lo6j7xbls"/><path class="vrpmrdbjw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:ibm-elo-engineering-insights" /></template>
