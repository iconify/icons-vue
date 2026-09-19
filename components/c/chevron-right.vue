<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uluxslbgc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":320,"height":512};
const content = `<path class="uluxslbgc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:chevron-right" /></template>
