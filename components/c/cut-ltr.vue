<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ikiveb-mx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ikiveb-mx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:cut-ltr" /></template>
