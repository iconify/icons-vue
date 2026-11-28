<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kilb8ccom.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kilb8ccom"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:file-zip-lock" /></template>
