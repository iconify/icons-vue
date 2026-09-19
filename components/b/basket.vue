<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qs5y83bnd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="qs5y83bnd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:basket" /></template>
