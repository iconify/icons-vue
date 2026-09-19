<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b3w5-xb3l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":384};
const content = `<path class="b3w5-xb3l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:center-focus-strong" /></template>
