<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nfre98ewh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nfre98ewh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:file-sync" /></template>
