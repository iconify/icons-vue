<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dx4b9vbux.css';
import '../../css/m/m24l3fbsc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="dx4b9vbux"/><path class="m24l3fbsc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:accumulation-snow" /></template>
