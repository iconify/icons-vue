<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xt5q-nbne.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xt5q-nbne"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:apple-homekit-dark" /></template>
