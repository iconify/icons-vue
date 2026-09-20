<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gw3haybgp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gw3haybgp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nrk:bluetooth" /></template>
