<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sk1zdgbuf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="sk1zdgbuf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:instapods-light" /></template>
