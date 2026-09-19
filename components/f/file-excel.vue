<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z25gs3brp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":512};
const content = `<path class="z25gs3brp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:file-excel" /></template>
