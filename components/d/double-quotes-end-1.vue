<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gwydrwbld.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":25,"height":24};
const content = `<path class="gwydrwbld"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:double-quotes-end-1" /></template>
