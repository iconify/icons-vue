<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gk-vu9vai.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gk-vu9vai"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:help-duotone-round" /></template>
