<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p7hb04whw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="p7hb04whw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:file-half-dashed" /></template>
