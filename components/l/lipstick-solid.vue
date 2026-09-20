<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zsjl_jbyd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="zsjl_jbyd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:lipstick-solid" /></template>
