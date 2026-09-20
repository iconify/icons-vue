<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qxbrcacrw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qxbrcacrw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:coffee-empty" /></template>
