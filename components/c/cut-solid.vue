<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qq10agx6h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="qq10agx6h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:cut-solid" /></template>
