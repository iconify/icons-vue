<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g4qz2rsxs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="g4qz2rsxs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:crutch" /></template>
