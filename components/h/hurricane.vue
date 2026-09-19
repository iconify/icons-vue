<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oo6qorwfu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":512};
const content = `<path class="oo6qorwfu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:hurricane" /></template>
