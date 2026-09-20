<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d5549tbpb.css';
import '../../css/z/zr90yfbxo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="d5549tbpb"/><path class="zr90yfbxo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:connectwise-screenconnect-light" /></template>
