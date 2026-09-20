<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bzc7ujhxo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="bzc7ujhxo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="osmic:bank-14" /></template>
