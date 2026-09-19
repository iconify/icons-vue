<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rzkml3d6r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1200,"height":1200};
const content = `<path class="rzkml3d6r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="el:barcode" /></template>
