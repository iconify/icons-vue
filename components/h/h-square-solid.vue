<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zlvbbpbkp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="zlvbbpbkp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:h-square-solid" /></template>
