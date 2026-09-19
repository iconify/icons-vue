<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ri8oai9ww.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":512};
const content = `<path class="ri8oai9ww"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:clipboard-question" /></template>
