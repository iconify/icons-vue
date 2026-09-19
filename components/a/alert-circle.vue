<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m-wfcwsse.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="m-wfcwsse"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:alert-circle" /></template>
