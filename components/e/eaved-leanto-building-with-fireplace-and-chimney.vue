<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zxppngd4j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="zxppngd4j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:eaved-leanto-building-with-fireplace-and-chimney" /></template>
