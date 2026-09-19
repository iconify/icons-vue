<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u8ivuxdxp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="u8ivuxdxp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:dog" /></template>
