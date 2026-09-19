<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x5cimwbxh.css';
import '../../css/m/mnxsi_e-u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="x5cimwbxh"/><path class="mnxsi_e-u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-rocket" /></template>
