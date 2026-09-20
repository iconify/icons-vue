<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zlxzqobyy.css';
import '../../css/y/y5z6dwezu.css';
import '../../css/a/akcxopd1a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zlxzqobyy"/><path class="y5z6dwezu"/><path class="akcxopd1a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:google-slides" /></template>
