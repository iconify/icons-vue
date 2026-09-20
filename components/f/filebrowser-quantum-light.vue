<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x9s81cs5j.css';
import '../../css/r/rm6kyddwf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="x9s81cs5j"/><path class="rm6kyddwf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:filebrowser-quantum-light" /></template>
