<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zx_p0ab0a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="zx_p0ab0a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:hitachi" /></template>
