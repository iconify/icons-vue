<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yr8u1glpl.css';
import '../../css/h/h4erxx0-o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yr8u1glpl"/><path class="h4erxx0-o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxl-algolia" /></template>
