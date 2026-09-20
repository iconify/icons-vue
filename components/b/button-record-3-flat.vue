<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i5780hbgv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="i5780hbgv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-color:button-record-3-flat" /></template>
