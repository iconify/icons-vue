<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x3lwmsbeo.css';
import '../../css/w/w17zy0bco.css';
import '../../css/d/dan73zqnv.css';
import '../../css/s/shroyfbxo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x3lwmsbeo"/><path clip-rule="evenodd" class="w17zy0bco"/><path class="dan73zqnv"/><path class="shroyfbxo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:columns-3-cog-bold" /></template>
