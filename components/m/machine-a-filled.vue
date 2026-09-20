<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oqou_g3dh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="oqou_g3dh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:machine-a-filled" /></template>
