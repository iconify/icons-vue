<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bcdp_lb8q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="bcdp_lb8q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:heart-cross-solid" /></template>
