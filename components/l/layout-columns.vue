<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qr4es86yo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="qr4es86yo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:layout-columns" /></template>
