<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/glo50x2fl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="glo50x2fl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:cplusplus" /></template>
