<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/htwi9xkgv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="htwi9xkgv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:ersatztv-dark" /></template>
