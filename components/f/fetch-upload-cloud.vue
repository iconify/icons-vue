<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m6z_u39ix.css';
import '../../css/k/kfaykc6be.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="m6z_u39ix"/><path class="kfaykc6be"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:fetch-upload-cloud" /></template>
