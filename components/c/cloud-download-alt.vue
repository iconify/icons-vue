<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mwznzsrok.css';
import '../../css/p/p8bzevp-b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mwznzsrok"/><path class="p8bzevp-b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:cloud-download-alt" /></template>
