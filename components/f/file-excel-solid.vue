<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c_vuxg-xv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="c_vuxg-xv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:file-excel-solid" /></template>
