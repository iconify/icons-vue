<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nhr1z4b3l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="nhr1z4b3l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:dynacat-dark" /></template>
