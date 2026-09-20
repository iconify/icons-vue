<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xwb06vbre.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":484,"height":512};
const content = `<path class="st1 xwb06vbre"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="academicons:conversation" /></template>
