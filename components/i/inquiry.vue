<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nu-q_73ca.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="nu-q_73ca"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:inquiry" /></template>
