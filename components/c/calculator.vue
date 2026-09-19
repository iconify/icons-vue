<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nvu2ttbxw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="nvu2ttbxw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icons8:calculator" /></template>
