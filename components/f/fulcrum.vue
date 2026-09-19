<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vyef6ab9k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":320,"height":512};
const content = `<path class="vyef6ab9k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-brands:fulcrum" /></template>
