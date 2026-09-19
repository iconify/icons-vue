<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rif_rfbrm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rif_rfbrm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:hitachi" /></template>
