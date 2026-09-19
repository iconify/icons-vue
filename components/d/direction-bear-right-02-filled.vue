<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/ggh9rqprt.css';
import '../../css/z/zee_subyv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ggh9rqprt"/><path class="zee_subyv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:direction-bear-right-02-filled" /></template>
