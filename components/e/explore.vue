<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oyx_v3onx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="oyx_v3onx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zondicons:explore" /></template>
