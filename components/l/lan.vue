<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zb93pobux.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zb93pobux"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:lan" /></template>
