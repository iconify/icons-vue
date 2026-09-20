<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vfj4zib1d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vfj4zib1d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:document-text2-filled" /></template>
