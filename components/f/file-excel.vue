<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nnso9-bfv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":512};
const content = `<path class="nnso9-bfv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-regular:file-excel" /></template>
