<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/it_ryvbvs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="it_ryvbvs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:disability-qcc-line" /></template>
