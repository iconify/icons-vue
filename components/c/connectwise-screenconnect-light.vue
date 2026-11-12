<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c35dru_2f.css';
import '../../css/z/zr90yfbxo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="c35dru_2f"/><path class="zr90yfbxo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:connectwise-screenconnect-light" /></template>
