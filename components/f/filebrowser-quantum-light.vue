<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t4_720ovn.css';
import '../../css/r/rm6kyddwf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="t4_720ovn"/><path class="rm6kyddwf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:filebrowser-quantum-light" /></template>
