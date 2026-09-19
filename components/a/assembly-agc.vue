<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dux5jwkjy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dux5jwkjy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:assembly-agc" /></template>
