<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ldsq-nn6r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ldsq-nn6r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:disk-filled" /></template>
