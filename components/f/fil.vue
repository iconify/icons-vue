<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lw205fbzg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="lw205fbzg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:fil" /></template>
