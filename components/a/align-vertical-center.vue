<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ld5934bvn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ld5934bvn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:align-vertical-center" /></template>
