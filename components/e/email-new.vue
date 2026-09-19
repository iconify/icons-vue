<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xb_pvbb1s.css';
import '../../css/s/sku11tm4k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="xb_pvbb1s"/><circle class="sku11tm4k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:email-new" /></template>
