<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yor-hx2rw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="yor-hx2rw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:composetoolbox-dark" /></template>
