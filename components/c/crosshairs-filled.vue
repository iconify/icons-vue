<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qeya9dbmf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="qeya9dbmf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:crosshairs-filled" /></template>
