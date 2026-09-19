<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ltms_d40t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ltms_d40t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:hand" /></template>
