<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zfyju2bjt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zfyju2bjt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:bank" /></template>
