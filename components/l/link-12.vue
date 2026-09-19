<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l81akxbbi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="l81akxbbi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:link-12" /></template>
