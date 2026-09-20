<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nwr3a161j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nwr3a161j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nrk:geo" /></template>
