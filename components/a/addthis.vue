<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kx3ploiaw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="kx3ploiaw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:addthis" /></template>
