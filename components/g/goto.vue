<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zkxodebuz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zkxodebuz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:goto" /></template>
