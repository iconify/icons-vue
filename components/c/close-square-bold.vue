<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sdi_z7bbh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sdi_z7bbh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:close-square-bold" /></template>
