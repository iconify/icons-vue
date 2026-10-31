<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x0u_55gvt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x0u_55gvt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:close-large-fill-round" /></template>
