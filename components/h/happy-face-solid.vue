<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fvtjo-b5j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="fvtjo-b5j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:happy-face-solid" /></template>
