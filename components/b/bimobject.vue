<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zbz72vbvf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="zbz72vbvf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-brands:bimobject" /></template>
