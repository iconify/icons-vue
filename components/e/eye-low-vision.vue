<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vrnc01brg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="vrnc01brg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:eye-low-vision" /></template>
