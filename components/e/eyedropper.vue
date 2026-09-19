<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zw3oh1bte.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1792,"height":1792};
const content = `<path class="zw3oh1bte"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:eyedropper" /></template>
