<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gx29xs_nz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gx29xs_nz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:cloud-close-fill-round" /></template>
