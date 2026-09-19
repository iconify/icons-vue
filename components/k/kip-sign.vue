<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zw4uwdbof.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":512};
const content = `<path class="zw4uwdbof"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:kip-sign" /></template>
