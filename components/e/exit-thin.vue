<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nf44gr3hp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nf44gr3hp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:exit-thin" /></template>
