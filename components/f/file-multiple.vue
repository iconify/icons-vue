<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z4si1_bgv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z4si1_bgv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi-light:file-multiple" /></template>
