<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sqv1ecbnn.css';
import '../../css/d/df0l6dbti.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="sqv1ecbnn"/><path class="df0l6dbti"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:game" /></template>
