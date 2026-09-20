<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bnb8sybom.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="bnb8sybom"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:align-front-1-solid" /></template>
