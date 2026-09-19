<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gndsrxvsa.css';
import '../../css/n/n7xm2kttp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="gndsrxvsa"/><path class="n7xm2kttp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:connection-send" /></template>
