<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vpje716il.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":384};
const content = `<path class="vpje716il"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:format-align-center" /></template>
