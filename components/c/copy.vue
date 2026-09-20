<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y25fkbbik.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="y25fkbbik"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:copy" /></template>
