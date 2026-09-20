<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z5et3fz1p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="z5et3fz1p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:lock-filled" /></template>
