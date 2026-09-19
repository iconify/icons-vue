<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/axvwdlb0z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="axvwdlb0z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:cyclone" /></template>
