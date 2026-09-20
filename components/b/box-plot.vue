<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sz1ljccmi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="sz1ljccmi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:box-plot" /></template>
