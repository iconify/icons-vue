<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hobd9v3ai.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":512};
const content = `<path class="hobd9v3ai"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:file-invoice" /></template>
