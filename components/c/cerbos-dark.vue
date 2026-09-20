<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gzx2bp9nm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gzx2bp9nm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:cerbos-dark" /></template>
