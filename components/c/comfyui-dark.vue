<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ad9uf7u_y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ad9uf7u_y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:comfyui-dark" /></template>
