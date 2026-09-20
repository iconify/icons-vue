<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vdltf5f5n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="vdltf5f5n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:half-star-1-solid" /></template>
