<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ey6w3zw8a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ey6w3zw8a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zondicons:dots-horizontal-triple" /></template>
