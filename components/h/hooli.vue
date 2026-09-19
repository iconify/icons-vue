<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/znqa3p1ks.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="znqa3p1ks"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-brands:hooli" /></template>
