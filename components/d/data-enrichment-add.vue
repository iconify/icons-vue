<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipkul0x-y.css';
import '../../css/k/kprce0ijz.css';
import '../../css/x/x8r3bo3uc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ipkul0x-y"/><path class="kprce0ijz"/><path class="x8r3bo3uc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:data-enrichment-add" /></template>
