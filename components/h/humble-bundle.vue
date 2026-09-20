<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sehd02_tk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="sehd02_tk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:humble-bundle" /></template>
