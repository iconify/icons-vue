<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zoldi4b3u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="zoldi4b3u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-color:arrow-transfer-diagonal-2-flat" /></template>
