<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eaj1adc-c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="eaj1adc-c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:lounger" /></template>
