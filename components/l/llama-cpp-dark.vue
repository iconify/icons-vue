<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cpgij3bke.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="cpgij3bke"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:llama-cpp-dark" /></template>
