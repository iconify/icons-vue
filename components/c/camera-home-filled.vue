<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m0sscpbxm.css';
import '../../css/t/toyc3i1pu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m0sscpbxm"/><path class="toyc3i1pu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:camera-home-filled" /></template>
