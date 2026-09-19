<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gl672qbji.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1000,"height":1000};
const content = `<path class="gl672qbji"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="websymbol:block" /></template>
