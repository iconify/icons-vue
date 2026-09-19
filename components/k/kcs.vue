<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/owhva1bsw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="owhva1bsw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:kcs" /></template>
