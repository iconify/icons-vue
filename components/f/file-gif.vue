<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uf7p7nbpx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uf7p7nbpx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:file-gif" /></template>
