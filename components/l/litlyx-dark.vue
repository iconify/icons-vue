<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yp0s7ccec.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="yp0s7ccec"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:litlyx-dark" /></template>
